<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_cn00-dz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="q_cn00-dz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:2-circle" {...props}></Icon>
