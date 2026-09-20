<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l2tf88blk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l2tf88blk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:bluesound" {...props}></Icon>
