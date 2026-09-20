<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dhr-1eb_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dhr-1eb_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:androidauto-logo-block" {...props}></Icon>
