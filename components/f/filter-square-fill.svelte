<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pd51n3b6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pd51n3b6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:filter-square-fill" {...props}></Icon>
