<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygy8l1bet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ygy8l1bet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bookmark-share" {...props}></Icon>
