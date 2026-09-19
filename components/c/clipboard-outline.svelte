<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/br71gpb8p.css';
import '../../css/i/izu9akmqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="br71gpb8p"/><rect class="izu9akmqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:clipboard-outline" {...props}></Icon>
