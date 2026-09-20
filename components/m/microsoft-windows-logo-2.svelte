<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_cg_6x-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k_cg_6x-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:microsoft-windows-logo-2" {...props}></Icon>
