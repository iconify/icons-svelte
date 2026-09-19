<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/un7tcbb8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="un7tcbb8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:fedora" {...props}></Icon>
