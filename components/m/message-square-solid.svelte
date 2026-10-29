<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sir6kksaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sir6kksaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:message-square-solid" {...props}></Icon>
