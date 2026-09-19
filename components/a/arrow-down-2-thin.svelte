<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5h_ypb5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f5h_ypb5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-down-2-thin" {...props}></Icon>
