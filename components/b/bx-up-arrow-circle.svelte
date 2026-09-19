<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twgo94b6k.css';
import '../../css/b/bc0bc3bjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="twgo94b6k"/><path class="bc0bc3bjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-up-arrow-circle" {...props}></Icon>
