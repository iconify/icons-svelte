<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a2x79mbfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="a2x79mbfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:dribbble" {...props}></Icon>
