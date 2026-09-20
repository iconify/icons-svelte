<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nfkp9qbtk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="nfkp9qbtk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:battery-exclamation" {...props}></Icon>
