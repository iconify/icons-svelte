<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/er27m0b0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="er27m0b0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-caret-up-circle" {...props}></Icon>
