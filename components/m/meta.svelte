<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ew-dqmb1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="ew-dqmb1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:meta" {...props}></Icon>
