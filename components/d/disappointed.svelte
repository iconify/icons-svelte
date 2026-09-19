<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fem986b2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fem986b2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:disappointed" {...props}></Icon>
