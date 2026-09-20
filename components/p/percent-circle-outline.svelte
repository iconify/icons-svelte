<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wjmc-obmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wjmc-obmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:percent-circle-outline" {...props}></Icon>
