<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ksuxf_bbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ksuxf_bbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:google-near-by-logo-block" {...props}></Icon>
