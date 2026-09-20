<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ds35rsb-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ds35rsb-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:cash-search-bold" {...props}></Icon>
