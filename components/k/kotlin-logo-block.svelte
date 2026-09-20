<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/idlnalfdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="idlnalfdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:kotlin-logo-block" {...props}></Icon>
