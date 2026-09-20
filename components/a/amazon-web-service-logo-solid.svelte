<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e96gj25qg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e96gj25qg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:amazon-web-service-logo-solid" {...props}></Icon>
