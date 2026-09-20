<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qz8pmwbck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qz8pmwbck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:balls" {...props}></Icon>
