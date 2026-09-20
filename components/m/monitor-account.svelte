<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvq8vlbfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kvq8vlbfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:monitor-account" {...props}></Icon>
