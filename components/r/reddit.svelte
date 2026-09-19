<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ku88zjgxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ku88zjgxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:reddit" {...props}></Icon>
