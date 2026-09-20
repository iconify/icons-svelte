<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/onxs8sd7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="onxs8sd7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:moon-15" {...props}></Icon>
