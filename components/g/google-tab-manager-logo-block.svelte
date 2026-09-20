<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jsctvp7wz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jsctvp7wz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:google-tab-manager-logo-block" {...props}></Icon>
