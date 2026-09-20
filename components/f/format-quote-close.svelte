<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/al9eygyeb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="al9eygyeb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:format-quote-close" {...props}></Icon>
