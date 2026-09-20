<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ss84kbcny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ss84kbcny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:kettle-empty-alert" {...props}></Icon>
