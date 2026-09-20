<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zdxk5xbmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zdxk5xbmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:clapperboard-open-filled" {...props}></Icon>
