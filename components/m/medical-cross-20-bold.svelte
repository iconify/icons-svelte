<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-ihs8boq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="o-ihs8boq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:medical-cross-20-bold" {...props}></Icon>
