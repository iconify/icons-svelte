<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dj2nbbceu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dj2nbbceu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:reddit" {...props}></Icon>
