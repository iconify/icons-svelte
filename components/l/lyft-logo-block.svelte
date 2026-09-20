<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xomw39bdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xomw39bdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:lyft-logo-block" {...props}></Icon>
