<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uw-bh2b7p.css';
import '../../css/r/rmwwi5nky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uw-bh2b7p"/><path class="rmwwi5nky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:cat" {...props}></Icon>
