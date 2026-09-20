<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udi048kbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="udi048kbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:analogue-logo-solid" {...props}></Icon>
