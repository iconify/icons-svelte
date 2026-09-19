<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qptu7mdrd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qptu7mdrd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:minus-sign" {...props}></Icon>
