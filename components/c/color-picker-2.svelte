<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wqh4zbbpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wqh4zbbpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:color-picker-2" {...props}></Icon>
