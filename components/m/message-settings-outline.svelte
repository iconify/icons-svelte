<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yusenx73p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yusenx73p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:message-settings-outline" {...props}></Icon>
