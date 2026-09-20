<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmkyjfmim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nmkyjfmim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:hourglass-end" {...props}></Icon>
