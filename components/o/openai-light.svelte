<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qrsjxybtj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":260};
const content = `<path class="qrsjxybtj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:openai-light" {...props}></Icon>
