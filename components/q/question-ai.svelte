<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/caly64b0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="caly64b0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:question-ai" {...props}></Icon>
