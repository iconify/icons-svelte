<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5z33k29f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t5z33k29f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:notification-bell-check-fill" {...props}></Icon>
