<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qwuzebcck.css';
import '../../css/e/ey9o68b2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qwuzebcck"/><path class="ey9o68b2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:megaphone-duotone" {...props}></Icon>
