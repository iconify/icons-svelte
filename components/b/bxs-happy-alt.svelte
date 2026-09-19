<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yuzur4lgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yuzur4lgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-happy-alt" {...props}></Icon>
