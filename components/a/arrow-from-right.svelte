<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u9keycb_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u9keycb_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-from-right" {...props}></Icon>
