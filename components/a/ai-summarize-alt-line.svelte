<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi52opb2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bi52opb2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:ai-summarize-alt-line" {...props}></Icon>
