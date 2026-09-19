<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-lg0wb-p.css';
import '../../css/w/w7cn_ur_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b-lg0wb-p"/><path class="w7cn_ur_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:mic-a" {...props}></Icon>
