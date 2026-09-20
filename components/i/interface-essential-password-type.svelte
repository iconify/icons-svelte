<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gmok0r2zk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gmok0r2zk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-password-type" {...props}></Icon>
