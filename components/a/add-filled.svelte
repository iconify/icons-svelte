<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ap5cqxbrg.css';
import '../../css/w/wzyv4j1bt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ap5cqxbrg"/><path class="wzyv4j1bt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:add-filled" {...props}></Icon>
