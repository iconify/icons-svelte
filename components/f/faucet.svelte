<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rv_m46rdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rv_m46rdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:faucet" {...props}></Icon>
