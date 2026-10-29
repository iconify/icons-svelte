<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1z9jtbha.css';
import '../../css/p/pllpyyb8j.css';
import '../../css/j/j07hvobsr.css';
import '../../css/u/u1q7c1byo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f1z9jtbha wm-k"/><path class="pllpyyb8j wm-k"/><path class="j07hvobsr wm-k"/><path class="u1q7c1byo wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:fish" {...props}></Icon>
