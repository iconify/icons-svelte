<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xmcxdubgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xmcxdubgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-u-turn-left-duotone" {...props}></Icon>
