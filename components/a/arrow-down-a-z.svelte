<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxxysjz2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="zxxysjz2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:arrow-down-a-z" {...props}></Icon>
