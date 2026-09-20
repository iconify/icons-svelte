<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/av8tbab7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="av8tbab7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:export-line" {...props}></Icon>
