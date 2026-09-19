<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m43opfbyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m43opfbyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-hide" {...props}></Icon>
