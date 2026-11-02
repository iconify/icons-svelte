<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z115utbvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z115utbvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:easy-in-out-fill" {...props}></Icon>
