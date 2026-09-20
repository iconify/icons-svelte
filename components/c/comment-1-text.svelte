<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mglbirb9o.css';
import '../../css/e/eu46usfmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mglbirb9o"/><path clip-rule="evenodd" class="eu46usfmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:comment-1-text" {...props}></Icon>
