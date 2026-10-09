<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ai8hlzasl.css';
import '../../css/y/y-q9b7fwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ai8hlzasl"/><path class="y-q9b7fwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bed-linen-20" {...props}></Icon>
