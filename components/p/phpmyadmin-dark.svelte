<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9t_xrbrh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o9t_xrbrh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:phpmyadmin-dark" {...props}></Icon>
