<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wyk3zk00o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wyk3zk00o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:ape" {...props}></Icon>
