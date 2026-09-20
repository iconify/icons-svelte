<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/shg2gacrl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="shg2gacrl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:checkmarx" {...props}></Icon>
