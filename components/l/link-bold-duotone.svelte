<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ln1f_4blw.css';
import '../../css/u/u8s4_onzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ln1f_4blw"/><path class="u8s4_onzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:link-bold-duotone" {...props}></Icon>
