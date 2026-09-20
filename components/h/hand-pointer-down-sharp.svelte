<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qz3n2vbdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qz3n2vbdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:hand-pointer-down-sharp" {...props}></Icon>
