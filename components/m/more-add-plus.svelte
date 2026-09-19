<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zb_u_rrkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zb_u_rrkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:more-add-plus" {...props}></Icon>
