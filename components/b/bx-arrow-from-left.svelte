<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kei-b7but.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kei-b7but"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-arrow-from-left" {...props}></Icon>
