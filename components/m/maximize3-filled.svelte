<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nblq55bty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nblq55bty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:maximize3-filled" {...props}></Icon>
