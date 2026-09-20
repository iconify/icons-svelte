<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qyf5y1bmq.css';
import '../../css/c/c74pkebbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qyf5y1bmq"/><path class="c74pkebbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-settings-toggle-horizontal" {...props}></Icon>
