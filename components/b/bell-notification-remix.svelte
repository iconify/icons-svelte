<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fe5lkbcpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fe5lkbcpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:bell-notification-remix" {...props}></Icon>
