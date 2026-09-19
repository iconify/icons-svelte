<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdxbv3bpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sdxbv3bpf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:cricket-ball-filled" {...props}></Icon>
