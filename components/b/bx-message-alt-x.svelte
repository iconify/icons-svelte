<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/snfofybnw.css';
import '../../css/x/x42zgxb_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="snfofybnw"/><path class="x42zgxb_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-message-alt-x" {...props}></Icon>
