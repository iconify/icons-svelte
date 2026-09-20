<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pz_le0wpd.css';
import '../../css/e/ewl5wjk4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pz_le0wpd"/><path class="ewl5wjk4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:notification-bell-pending-fill" {...props}></Icon>
