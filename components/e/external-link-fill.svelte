<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iyn4ahb-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iyn4ahb-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:external-link-fill" {...props}></Icon>
