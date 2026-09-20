<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_0lpxb2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s_0lpxb2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:gdgt-logo-block" {...props}></Icon>
