<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nw5jyccdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nw5jyccdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:refund-line" {...props}></Icon>
