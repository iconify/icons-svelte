<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6j498kyp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n6j498kyp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:cloud-slow-wind" {...props}></Icon>
