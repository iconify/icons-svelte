<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxp96ub2p.css';
import '../../css/z/zcyb7gkkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qxp96ub2p"/><path class="zcyb7gkkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:mailbox-20" {...props}></Icon>
