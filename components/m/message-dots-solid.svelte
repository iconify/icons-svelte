<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwzo7wbpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pwzo7wbpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:message-dots-solid" {...props}></Icon>
