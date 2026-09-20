<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3qjh-7lx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b3qjh-7lx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:cam-disk-10k" {...props}></Icon>
