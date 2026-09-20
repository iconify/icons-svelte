<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lyv6d8bin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lyv6d8bin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:american-football-fill" {...props}></Icon>
