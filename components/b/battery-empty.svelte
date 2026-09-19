<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqw61wbys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="zqw61wbys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:battery-empty" {...props}></Icon>
