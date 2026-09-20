<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fkjjvlbhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="fkjjvlbhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:moon-alt-waxing-crescent-5" {...props}></Icon>
