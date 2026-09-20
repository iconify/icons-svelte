<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hy6w7gb6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hy6w7gb6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:call-forwarding-outgoing-1-bold" {...props}></Icon>
