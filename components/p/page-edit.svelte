<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r6842ab4y.css';
import '../../css/m/mx48p9b3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="r6842ab4y"/><path class="mx48p9b3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:page-edit" {...props}></Icon>
