<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/adw_cvhpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="adw_cvhpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:geforce-now-logo-solid" {...props}></Icon>
