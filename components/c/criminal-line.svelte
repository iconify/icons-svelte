<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5bblhglr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c5bblhglr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:criminal-line" {...props}></Icon>
