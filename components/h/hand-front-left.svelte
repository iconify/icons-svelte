<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f8tmofbuw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f8tmofbuw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:hand-front-left" {...props}></Icon>
