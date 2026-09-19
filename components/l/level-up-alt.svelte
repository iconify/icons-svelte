<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ynqrycc5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="ynqrycc5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:level-up-alt" {...props}></Icon>
