<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eqelubcax.css';
import '../../css/r/rfo4zzbxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eqelubcax"/><path class="rfo4zzbxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-in-up-square-half-filled" {...props}></Icon>
