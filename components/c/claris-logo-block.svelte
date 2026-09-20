<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vr0vqrbwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vr0vqrbwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:claris-logo-block" {...props}></Icon>
