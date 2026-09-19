<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t95140brd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="t95140brd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:odnoklassniki" {...props}></Icon>
