<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abwkqfblz.css';
import '../../css/j/j7p02hblv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="abwkqfblz"/><path class="j7p02hblv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hair-dryer-20" {...props}></Icon>
