<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oyz25t6vc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="oyz25t6vc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:arrow-down" {...props}></Icon>
