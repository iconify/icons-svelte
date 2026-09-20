<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wlp_js4cf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wlp_js4cf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pequeroku-dark" {...props}></Icon>
