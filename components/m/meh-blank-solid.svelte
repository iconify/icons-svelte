<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hzow2z1zo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hzow2z1zo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:meh-blank-solid" {...props}></Icon>
