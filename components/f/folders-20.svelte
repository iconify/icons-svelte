<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3n57acnu.css';
import '../../css/u/ufjhi98xb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="u3n57acnu"/><path class="ufjhi98xb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:folders-20" {...props}></Icon>
