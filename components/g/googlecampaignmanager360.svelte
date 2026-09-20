<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sxpv5-bhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sxpv5-bhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:googlecampaignmanager360" {...props}></Icon>
