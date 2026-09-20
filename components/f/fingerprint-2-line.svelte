<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e48hl62yw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e48hl62yw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fingerprint-2-line" {...props}></Icon>
