<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wkdp2-btv.css';
import '../../css/g/g9wjd3b3c.css';
import '../../css/t/t6vzpjbvb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wkdp2-btv"/><path class="g9wjd3b3c"/><path class="t6vzpjbvb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:more-vertical" {...props}></Icon>
