<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdy-seb3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fdy-seb3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:keyboard-hide" {...props}></Icon>
