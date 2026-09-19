<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ns3mynbwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ns3mynbwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:open-mailbox-raised-flag" {...props}></Icon>
