<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3bs-cb3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="v3bs-cb3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:forumbee" {...props}></Icon>
