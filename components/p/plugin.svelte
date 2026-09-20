<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qvr0h0xiz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qvr0h0xiz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:plugin" {...props}></Icon>
