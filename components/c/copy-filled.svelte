<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nlczntbgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nlczntbgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:copy-filled" {...props}></Icon>
