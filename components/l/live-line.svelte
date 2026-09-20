<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/siopq7bvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="siopq7bvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:live-line" {...props}></Icon>
