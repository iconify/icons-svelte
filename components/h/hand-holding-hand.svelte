<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lxvidob-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="lxvidob-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:hand-holding-hand" {...props}></Icon>
