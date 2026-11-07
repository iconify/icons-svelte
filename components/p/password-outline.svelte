<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/caw1b0bno.css';
import '../../css/f/fiugtjbdq.css';
import '../../css/h/hvf_gzblv.css';
import '../../css/h/hc3npei1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="caw1b0bno"/><path class="fiugtjbdq"/><path class="hvf_gzblv"/><path clip-rule="evenodd" class="hc3npei1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:password-outline" {...props}></Icon>
