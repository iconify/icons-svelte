<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ti26dd_bv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ti26dd_bv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:notification-bell-snooze-2-fill" {...props}></Icon>
