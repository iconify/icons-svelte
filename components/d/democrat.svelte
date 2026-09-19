<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdptq_7jw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="gdptq_7jw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:democrat" {...props}></Icon>
