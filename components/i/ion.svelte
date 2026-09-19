<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/say8_yggr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="say8_yggr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:ion" {...props}></Icon>
