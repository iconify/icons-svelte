<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xu2zzwf5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":31,"height":24};
const content = `<path class="xu2zzwf5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:quote-a-right" {...props}></Icon>
