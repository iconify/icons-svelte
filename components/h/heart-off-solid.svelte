<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jp_l5hn1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jp_l5hn1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:heart-off-solid" {...props}></Icon>
