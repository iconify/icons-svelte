<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emv79z_7s.css';
import '../../css/u/uedxr2vmg.css';
import '../../css/b/b4j8a-5qc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="emv79z_7s"/><path class="uedxr2vmg"/><path class="b4j8a-5qc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:quote-20-bold" {...props}></Icon>
