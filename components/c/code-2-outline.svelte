<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gtxp16bpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gtxp16bpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:code-2-outline" {...props}></Icon>
