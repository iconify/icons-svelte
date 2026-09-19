<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yxiue0b3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yxiue0b3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:notification-deactivated" {...props}></Icon>
