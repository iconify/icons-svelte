<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vheb2-beq.css';
import '../../css/u/ubakjmb1l.css';
import '../../css/k/kjfotn-5m.css';
import '../../css/t/t0ktzn_8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vheb2-beq"/><path clip-rule="evenodd" class="ubakjmb1l"/><path class="kjfotn-5m"/><path class="t0ktzn_8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:notification-unread-lines-outline" {...props}></Icon>
