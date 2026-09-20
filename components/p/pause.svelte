<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qb3gftglq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qb3gftglq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:pause" {...props}></Icon>
