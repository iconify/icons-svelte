<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rznx5gbgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rznx5gbgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:chart-bar" {...props}></Icon>
