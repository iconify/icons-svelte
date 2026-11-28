<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3z-7f-xi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i3z-7f-xi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:file-alert-solid" {...props}></Icon>
