<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfe4qxb_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rfe4qxb_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:lock-keyhole" {...props}></Icon>
