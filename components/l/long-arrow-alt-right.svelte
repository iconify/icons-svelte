<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-wuhccyp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="s-wuhccyp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:long-arrow-alt-right" {...props}></Icon>
