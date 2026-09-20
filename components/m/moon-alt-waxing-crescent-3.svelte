<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s59zdp_-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="s59zdp_-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:moon-alt-waxing-crescent-3" {...props}></Icon>
