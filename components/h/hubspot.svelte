<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0e02lbkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="m0e02lbkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:hubspot" {...props}></Icon>
