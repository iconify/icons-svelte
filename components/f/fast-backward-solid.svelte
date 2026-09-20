<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/szc-0q-at.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="szc-0q-at"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:fast-backward-solid" {...props}></Icon>
