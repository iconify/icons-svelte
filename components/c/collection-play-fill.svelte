<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ne0xqbbgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ne0xqbbgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:collection-play-fill" {...props}></Icon>
