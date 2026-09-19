<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qkx9uxboa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qkx9uxboa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:heart-minus" {...props}></Icon>
