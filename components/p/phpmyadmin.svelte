<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ybgh70bly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ybgh70bly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:phpmyadmin" {...props}></Icon>
