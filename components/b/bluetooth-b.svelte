<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1w7zg6hz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="u1w7zg6hz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:bluetooth-b" {...props}></Icon>
