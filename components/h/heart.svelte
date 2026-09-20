<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gmmau1b9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="gmmau1b9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:heart" {...props}></Icon>
