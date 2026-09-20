<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ltsx_kb3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ltsx_kb3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:p-arrow-right" {...props}></Icon>
