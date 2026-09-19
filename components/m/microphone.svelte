<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fe0j13bar.css';
import '../../css/y/y7bs-t6_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fe0j13bar"/><path class="y7bs-t6_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:microphone" {...props}></Icon>
