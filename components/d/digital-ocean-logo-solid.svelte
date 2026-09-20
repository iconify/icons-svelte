<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rmpx7kb_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rmpx7kb_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:digital-ocean-logo-solid" {...props}></Icon>
