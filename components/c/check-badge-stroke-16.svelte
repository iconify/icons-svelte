<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txh_v0bvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="txh_v0bvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:check-badge-stroke-16" {...props}></Icon>
