<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wgpfcmb5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wgpfcmb5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:radius-solid" {...props}></Icon>
