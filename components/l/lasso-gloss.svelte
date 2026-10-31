<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-h0aogne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j-h0aogne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:lasso-gloss" {...props}></Icon>
