<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxb47rbac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fxb47rbac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:adobe-indesign-logo-block" {...props}></Icon>
