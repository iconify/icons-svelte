<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fq3--h1on.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fq3--h1on"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cellphone-2-horizontal-fill" {...props}></Icon>
