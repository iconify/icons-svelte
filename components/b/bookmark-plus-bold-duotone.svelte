<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qy2y5qfqd.css';
import '../../css/v/v0qr5rb-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qy2y5qfqd"/><path class="v0qr5rb-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bookmark-plus-bold-duotone" {...props}></Icon>
