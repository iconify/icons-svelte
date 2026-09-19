<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xxmiot2cq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xxmiot2cq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:calendar3-week-fill" {...props}></Icon>
