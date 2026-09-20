<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ucsmcqbrq.css';
import '../../css/f/f1ouj-bgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ucsmcqbrq"/><path class="f1ouj-bgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:document-ai-filled" {...props}></Icon>
