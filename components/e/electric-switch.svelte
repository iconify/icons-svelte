<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxlo8zbaj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zxlo8zbaj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:electric-switch" {...props}></Icon>
