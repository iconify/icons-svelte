<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qlm5ewnxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qlm5ewnxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-contact" {...props}></Icon>
