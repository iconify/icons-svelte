<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ex1x372fr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ex1x372fr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:close-line" {...props}></Icon>
