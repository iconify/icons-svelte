<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fq-33qbhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fq-33qbhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:diamond-minus-fill" {...props}></Icon>
