<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fos04kb5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fos04kb5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:chess-king" {...props}></Icon>
