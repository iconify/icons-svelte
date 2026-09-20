<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pht-9fylt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pht-9fylt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:eye-slash" {...props}></Icon>
