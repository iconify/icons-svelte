<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhig7ybyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yhig7ybyd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-question-outline" {...props}></Icon>
