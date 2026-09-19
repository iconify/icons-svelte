<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tw_r_-5rj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tw_r_-5rj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:hexagon-fill" {...props}></Icon>
