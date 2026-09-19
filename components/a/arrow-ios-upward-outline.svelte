<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lxt4qmc0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lxt4qmc0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:arrow-ios-upward-outline" {...props}></Icon>
