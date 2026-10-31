<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oznuf_q2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oznuf_q2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:owl-fill-round" {...props}></Icon>
