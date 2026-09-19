<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7cbxcbrc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="n7cbxcbrc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:refresh" {...props}></Icon>
