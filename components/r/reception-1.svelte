<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lh_4jt-7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lh_4jt-7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:reception-1" {...props}></Icon>
