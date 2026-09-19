<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rp4p6dprq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rp4p6dprq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:hsr" {...props}></Icon>
