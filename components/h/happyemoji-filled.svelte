<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0v3-lpsq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s0v3-lpsq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:happyemoji-filled" {...props}></Icon>
