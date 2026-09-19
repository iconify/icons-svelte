<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iml59opdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":387,"height":512};
const content = `<path class="iml59opdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:rollup" {...props}></Icon>
