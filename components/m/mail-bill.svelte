<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hn-044cbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":448};
const content = `<path class="hn-044cbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:mail-bill" {...props}></Icon>
