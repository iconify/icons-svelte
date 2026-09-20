<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vh_dlqbyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="vh_dlqbyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-vertical-menu-right" {...props}></Icon>
