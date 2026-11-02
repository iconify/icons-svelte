<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k7uhn5aqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k7uhn5aqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:phone-call-fill" {...props}></Icon>
