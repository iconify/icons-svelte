<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ah2imfolq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ah2imfolq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cards-playing-diamond-multiple" {...props}></Icon>
