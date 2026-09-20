<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xahhzk8rq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xahhzk8rq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:eyedropper" {...props}></Icon>
