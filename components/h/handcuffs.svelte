<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygj57klac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="ygj57klac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:handcuffs" {...props}></Icon>
