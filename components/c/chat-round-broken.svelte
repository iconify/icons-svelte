<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nb59sp9du.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nb59sp9du"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-round-broken" {...props}></Icon>
