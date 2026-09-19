<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sknu5wjce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sknu5wjce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:diamond-01" {...props}></Icon>
