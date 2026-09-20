<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/po0j042em.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="po0j042em"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:phone" {...props}></Icon>
