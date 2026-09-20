<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sl-22xbtd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sl-22xbtd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:mask" {...props}></Icon>
