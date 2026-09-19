<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rqe6wgboz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rqe6wgboz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:chevron-up-circle-filled" {...props}></Icon>
