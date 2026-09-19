<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g8x6l9lic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g8x6l9lic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:curtains" {...props}></Icon>
