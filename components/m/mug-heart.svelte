<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hs782kb2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hs782kb2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:mug-heart" {...props}></Icon>
