<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abetf7bgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="abetf7bgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:cloudsmith" {...props}></Icon>
