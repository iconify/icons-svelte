<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a5r3rjbeg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a5r3rjbeg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:mail-question" {...props}></Icon>
