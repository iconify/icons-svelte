<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/spgqeiahh.css';
import '../../css/x/xov8m50ru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="spgqeiahh"/><path class="xov8m50ru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:cloud-sun-stroke-20" {...props}></Icon>
