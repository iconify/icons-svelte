<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9t0xab1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m9t0xab1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:mailbox" {...props}></Icon>
