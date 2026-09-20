<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yu35q8g9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yu35q8g9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:mobile-alt" {...props}></Icon>
