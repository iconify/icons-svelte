<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmlk19rpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qmlk19rpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cash-plus" {...props}></Icon>
