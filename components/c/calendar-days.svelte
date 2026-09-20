<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxxjieq7t.css';
import '../../css/l/lec3gmbyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nxxjieq7t"/><path class="lec3gmbyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:calendar-days" {...props}></Icon>
