<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/krspf2vus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="krspf2vus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:chart5" {...props}></Icon>
