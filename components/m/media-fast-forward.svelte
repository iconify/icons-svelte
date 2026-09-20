<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lm756ob8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lm756ob8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:media-fast-forward" {...props}></Icon>
