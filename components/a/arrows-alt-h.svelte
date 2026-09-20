<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rcksdoptn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rcksdoptn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:arrows-alt-h" {...props}></Icon>
