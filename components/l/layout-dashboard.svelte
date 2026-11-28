<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iezj82sdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="iezj82sdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:layout-dashboard" {...props}></Icon>
