<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rc8791b5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rc8791b5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:community-line" {...props}></Icon>
