<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tos4f_s-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tos4f_s-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:arrow-triangle-loop" {...props}></Icon>
