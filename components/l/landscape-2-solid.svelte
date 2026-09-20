<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q0x-y3z1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="q0x-y3z1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:landscape-2-solid" {...props}></Icon>
