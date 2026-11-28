<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iw_uv8bpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iw_uv8bpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:octagon-solid" {...props}></Icon>
