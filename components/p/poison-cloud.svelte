<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2av_51yi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w2av_51yi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:poison-cloud" {...props}></Icon>
