<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4lny_b2c.css';
import '../../css/e/ey5fvkbdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":16};
const content = `<path class="p4lny_b2c"/><path class="ey5fvkbdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:reply" {...props}></Icon>
