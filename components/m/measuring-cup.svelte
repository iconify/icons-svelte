<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjy5pccxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cjy5pccxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:measuring-cup" {...props}></Icon>
