<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yu6sshm_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yu6sshm_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cooldown-line" {...props}></Icon>
