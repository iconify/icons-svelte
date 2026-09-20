<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ejm67ybkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ejm67ybkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:letter-spacing-fill" {...props}></Icon>
