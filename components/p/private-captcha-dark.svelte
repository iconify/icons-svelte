<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ykbdo5b1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ykbdo5b1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:private-captcha-dark" {...props}></Icon>
