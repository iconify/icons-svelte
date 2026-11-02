<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lti8xrsjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lti8xrsjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:camcorder-fill" {...props}></Icon>
