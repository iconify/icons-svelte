<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p206_ts3m.css';
import '../../css/u/u3j01bgpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p206_ts3m secondary"/><path class="primary u3j01bgpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:navigation-duo" {...props}></Icon>
