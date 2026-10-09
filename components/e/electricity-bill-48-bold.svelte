<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qk4s-jblr.css';
import '../../css/c/c7rnb2klb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qk4s-jblr"/><path class="c7rnb2klb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:electricity-bill-48-bold" {...props}></Icon>
