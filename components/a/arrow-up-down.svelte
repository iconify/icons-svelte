<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uozztrbrs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="uozztrbrs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:arrow-up-down" {...props}></Icon>
