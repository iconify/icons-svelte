<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fz4uxmb5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fz4uxmb5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:anchor-line" {...props}></Icon>
