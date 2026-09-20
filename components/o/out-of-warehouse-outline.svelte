<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mee7l434j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mee7l434j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:out-of-warehouse-outline" {...props}></Icon>
