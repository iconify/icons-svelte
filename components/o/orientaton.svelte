<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oi3532bvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":20};
const content = `<path class="oi3532bvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:orientaton" {...props}></Icon>
