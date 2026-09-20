<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dig0yubbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dig0yubbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:location-16" {...props}></Icon>
