<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zdpl5iqvt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zdpl5iqvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:progress-alert" {...props}></Icon>
