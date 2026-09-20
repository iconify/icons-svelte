<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iz-uxmbck.css';
import '../../css/r/r8i2-5bdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iz-uxmbck"/><path class="r8i2-5bdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:aircraft-chopper-2-bold" {...props}></Icon>
