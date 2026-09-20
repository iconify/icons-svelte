<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zwbuhqa_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="zwbuhqa_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:cloud-wifi" {...props}></Icon>
