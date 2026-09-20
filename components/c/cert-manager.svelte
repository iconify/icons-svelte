<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/za7xkl_6x.css';
import '../../css/x/xd0ybnb5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="za7xkl_6x"/><path class="xd0ybnb5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cert-manager" {...props}></Icon>
