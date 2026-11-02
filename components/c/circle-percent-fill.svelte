<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5589jwrs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x5589jwrs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:circle-percent-fill" {...props}></Icon>
