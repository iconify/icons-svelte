<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nwrbb51dl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nwrbb51dl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:face-id-solid" {...props}></Icon>
