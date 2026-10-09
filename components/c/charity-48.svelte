<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g81g92bif.css';
import '../../css/w/wrr9qib1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="g81g92bif"/><path class="wrr9qib1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:charity-48" {...props}></Icon>
