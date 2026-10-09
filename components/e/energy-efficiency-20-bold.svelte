<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sut7r2bvd.css';
import '../../css/o/oebaf-blw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="sut7r2bvd"/><path class="oebaf-blw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:energy-efficiency-20-bold" {...props}></Icon>
