<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ao25eccbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ao25eccbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:refresh" {...props}></Icon>
