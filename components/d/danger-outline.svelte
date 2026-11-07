<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqdm2xbfi.css';
import '../../css/p/prq9nybvi.css';
import '../../css/d/d71ngcbgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iqdm2xbfi"/><path class="prq9nybvi"/><path clip-rule="evenodd" class="d71ngcbgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:danger-outline" {...props}></Icon>
