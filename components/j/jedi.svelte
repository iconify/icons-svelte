<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zfo9l1-9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="zfo9l1-9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:jedi" {...props}></Icon>
