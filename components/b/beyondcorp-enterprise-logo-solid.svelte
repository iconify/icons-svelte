<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0fy9ld3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z0fy9ld3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:beyondcorp-enterprise-logo-solid" {...props}></Icon>
