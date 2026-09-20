<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itr0olbhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="itr0olbhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:notification-bell-cross-fill" {...props}></Icon>
