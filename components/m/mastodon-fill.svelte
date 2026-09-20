<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mo5_wobsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mo5_wobsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:mastodon-fill" {...props}></Icon>
