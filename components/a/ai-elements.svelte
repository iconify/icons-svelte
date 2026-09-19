<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txgz3-bpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="txgz3-bpf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:ai-elements" {...props}></Icon>
