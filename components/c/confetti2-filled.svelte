<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wct_gyo-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wct_gyo-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:confetti2-filled" {...props}></Icon>
