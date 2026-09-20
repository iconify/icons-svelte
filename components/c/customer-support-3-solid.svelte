<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vn6uicxet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vn6uicxet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:customer-support-3-solid" {...props}></Icon>
