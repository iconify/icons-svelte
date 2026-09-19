<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/viih6gzay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="viih6gzay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-bible" {...props}></Icon>
