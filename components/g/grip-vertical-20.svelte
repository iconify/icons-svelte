<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9pad14ep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="c9pad14ep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:grip-vertical-20" {...props}></Icon>
