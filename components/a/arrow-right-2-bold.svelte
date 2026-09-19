<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xqv85o6cb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xqv85o6cb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-right-2-bold" {...props}></Icon>
