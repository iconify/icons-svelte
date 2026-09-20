<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-pg_gpqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="z-pg_gpqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:portrait-solid" {...props}></Icon>
