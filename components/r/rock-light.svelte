<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/srrlq36sc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="srrlq36sc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:rock-light" {...props}></Icon>
