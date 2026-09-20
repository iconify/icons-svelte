<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u9vm1jp9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u9vm1jp9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:review-board-dark" {...props}></Icon>
