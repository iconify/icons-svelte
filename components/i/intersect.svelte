<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hy5g290lb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hy5g290lb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:intersect" {...props}></Icon>
