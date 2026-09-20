<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vfa599b0o.css';
import '../../css/p/pc_zkzb0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vfa599b0o"/><path class="pc_zkzb0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:bilibili-logo-bold" {...props}></Icon>
