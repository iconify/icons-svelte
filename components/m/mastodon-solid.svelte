<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ei03hwbsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ei03hwbsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:mastodon-solid" {...props}></Icon>
