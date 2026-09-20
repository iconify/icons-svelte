<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qx0gpq2uu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qx0gpq2uu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:microsoft-dynamics-logo-block" {...props}></Icon>
