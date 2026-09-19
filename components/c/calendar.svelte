<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thmup_0jj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="thmup_0jj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:calendar" {...props}></Icon>
