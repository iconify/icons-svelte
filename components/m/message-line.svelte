<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ou6xlkbcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ou6xlkbcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:message-line" {...props}></Icon>
