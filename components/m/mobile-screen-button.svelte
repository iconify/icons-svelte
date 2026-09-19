<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9b7z7bdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="e9b7z7bdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:mobile-screen-button" {...props}></Icon>
