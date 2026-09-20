<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/my86mbcer.css';
import '../../css/v/v5iwbub1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="my86mbcer"/><path class="v5iwbub1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:alert-bell-notification-2-bold" {...props}></Icon>
