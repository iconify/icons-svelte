<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2h20g36s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h2h20g36s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:phone-call-line" {...props}></Icon>
