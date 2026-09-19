<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/glx1udbwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="glx1udbwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:republican" {...props}></Icon>
