<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt1vuebfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="dt1vuebfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:bed" {...props}></Icon>
