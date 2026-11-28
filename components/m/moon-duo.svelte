<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sgzmasisn.css';
import '../../css/x/xycz9duzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary sgzmasisn"/><path class="primary xycz9duzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:moon-duo" {...props}></Icon>
