<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lhcl_vheq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lhcl_vheq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-caret-up" {...props}></Icon>
