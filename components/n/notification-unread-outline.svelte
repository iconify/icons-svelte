<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vheb2-beq.css';
import '../../css/u/ubakjmb1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vheb2-beq"/><path clip-rule="evenodd" class="ubakjmb1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:notification-unread-outline" {...props}></Icon>
