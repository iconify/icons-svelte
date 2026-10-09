<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9eubhbjc.css';
import '../../css/z/zp0_hubyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="z9eubhbjc"/><path class="zp0_hubyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:battery-fire-20" {...props}></Icon>
