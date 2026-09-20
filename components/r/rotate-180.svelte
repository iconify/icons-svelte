<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nfqvy5bci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nfqvy5bci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:rotate-180" {...props}></Icon>
