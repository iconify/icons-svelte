<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-v9j-zlm.css';
import '../../css/t/tsvt3bbpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="e-v9j-zlm"/><path class="tsvt3bbpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-loading-25-percent-1" {...props}></Icon>
