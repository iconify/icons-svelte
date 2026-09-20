<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfpj7sbvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yfpj7sbvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:document-scanning-mode-camera-bold" {...props}></Icon>
