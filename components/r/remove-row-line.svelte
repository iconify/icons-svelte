<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhh2g9tnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yhh2g9tnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:remove-row-line" {...props}></Icon>
