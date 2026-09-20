<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ukaq_cb7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ukaq_cb7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arrow-right-up-circle-line" {...props}></Icon>
