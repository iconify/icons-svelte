<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u_3ysdb5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="u_3ysdb5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:credit-card-fill-16" {...props}></Icon>
