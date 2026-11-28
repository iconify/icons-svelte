<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bnmr3zbwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bnmr3zbwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:monitor-play" {...props}></Icon>
