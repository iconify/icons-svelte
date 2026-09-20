<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f89mspbzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f89mspbzj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:pycqa" {...props}></Icon>
