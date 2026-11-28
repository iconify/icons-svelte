<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kgrbh47_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kgrbh47_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:comet" {...props}></Icon>
