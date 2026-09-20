<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fm8x86b9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fm8x86b9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:content-cut" {...props}></Icon>
