<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0wpv1pbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e0wpv1pbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chicken-line" {...props}></Icon>
