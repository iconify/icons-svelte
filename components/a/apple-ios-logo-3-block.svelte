<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_z-ilrca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k_z-ilrca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:apple-ios-logo-3-block" {...props}></Icon>
