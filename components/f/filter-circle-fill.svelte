<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/co36qraxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="co36qraxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:filter-circle-fill" {...props}></Icon>
