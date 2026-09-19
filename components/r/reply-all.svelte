<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/scsv6ubbs.css';
import '../../css/n/nxv1jnq8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="scsv6ubbs"/><path class="nxv1jnq8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:reply-all" {...props}></Icon>
