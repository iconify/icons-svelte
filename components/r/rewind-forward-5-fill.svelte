<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nunlv_k3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nunlv_k3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rewind-forward-5-fill" {...props}></Icon>
