<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fae0gccdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="fae0gccdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:5" {...props}></Icon>
