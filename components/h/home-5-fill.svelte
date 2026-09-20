<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/le2wawnyp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="le2wawnyp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:home-5-fill" {...props}></Icon>
