<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dohn-wkdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="dohn-wkdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:forward-bar-20-solid" {...props}></Icon>
