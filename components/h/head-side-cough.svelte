<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7o_thdxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="b7o_thdxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:head-side-cough" {...props}></Icon>
