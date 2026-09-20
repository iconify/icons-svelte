<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n2pjjkbqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n2pjjkbqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:google-drive-logo-1-block" {...props}></Icon>
