<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xtxym15qt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xtxym15qt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-down-arrow-alt" {...props}></Icon>
