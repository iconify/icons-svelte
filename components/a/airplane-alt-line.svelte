<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7o185bhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d7o185bhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:airplane-alt-line" {...props}></Icon>
