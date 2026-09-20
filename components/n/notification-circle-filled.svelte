<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5lze41zi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t5lze41zi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:notification-circle-filled" {...props}></Icon>
