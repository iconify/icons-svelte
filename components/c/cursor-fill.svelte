<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cr6ru96_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cr6ru96_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cursor-fill" {...props}></Icon>
