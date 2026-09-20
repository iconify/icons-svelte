<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pp3xq4blr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pp3xq4blr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:drive-safety" {...props}></Icon>
