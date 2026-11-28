<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ic45bnbsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ic45bnbsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:piano" {...props}></Icon>
