<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a2m1vj1ta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a2m1vj1ta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:aptabase" {...props}></Icon>
