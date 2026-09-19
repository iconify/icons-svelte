<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/du2py5bet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":407,"height":512};
const content = `<path class="du2py5bet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:raspberry-pi" {...props}></Icon>
