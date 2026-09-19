<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ub1ttxb2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ub1ttxb2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:body-part-six-pack" {...props}></Icon>
