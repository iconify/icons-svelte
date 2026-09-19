<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d08fjthkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d08fjthkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-right-arrow-alt" {...props}></Icon>
