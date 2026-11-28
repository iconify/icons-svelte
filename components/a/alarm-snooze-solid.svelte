<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vkb1cls-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vkb1cls-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:alarm-snooze-solid" {...props}></Icon>
