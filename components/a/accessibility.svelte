<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n38-vj_wj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":14};
const content = `<path class="n38-vj_wj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:accessibility" {...props}></Icon>
