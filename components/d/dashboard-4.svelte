<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dmvkqpbgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dmvkqpbgr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:dashboard-4" {...props}></Icon>
