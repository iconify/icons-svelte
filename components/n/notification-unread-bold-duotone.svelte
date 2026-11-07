<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gv4wotbsh.css';
import '../../css/b/b133qtshg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gv4wotbsh"/><path class="b133qtshg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:notification-unread-bold-duotone" {...props}></Icon>
