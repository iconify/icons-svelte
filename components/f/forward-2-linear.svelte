<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0xwtobcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o0xwtobcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:forward-2-linear" {...props}></Icon>
