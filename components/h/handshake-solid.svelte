<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jr70wvhdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jr70wvhdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:handshake-solid" {...props}></Icon>
