<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddwa9ybpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ddwa9ybpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:panel-glass-door-3-locked" {...props}></Icon>
