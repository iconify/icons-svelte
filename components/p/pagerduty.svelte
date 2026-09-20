<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i7o97wbdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i7o97wbdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:pagerduty" {...props}></Icon>
