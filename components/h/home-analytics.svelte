<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s69kkir1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s69kkir1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:home-analytics" {...props}></Icon>
