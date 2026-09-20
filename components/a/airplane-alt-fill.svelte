<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xdu34r1wc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xdu34r1wc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:airplane-alt-fill" {...props}></Icon>
