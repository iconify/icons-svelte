<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q19_zcben.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q19_zcben"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:play-bar-three" {...props}></Icon>
