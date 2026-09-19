<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zic8crbou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zic8crbou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:basket3-fill" {...props}></Icon>
