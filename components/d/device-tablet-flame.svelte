<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0l7-ebsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z0l7-ebsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-tablet-flame" {...props}></Icon>
