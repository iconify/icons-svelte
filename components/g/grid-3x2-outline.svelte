<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vj6svecim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vj6svecim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:grid-3x2-outline" {...props}></Icon>
