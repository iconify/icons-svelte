<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wa8xxfbmy.css';
import '../../css/s/sms_5zbgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wa8xxfbmy"/><path class="sms_5zbgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:copy" {...props}></Icon>
