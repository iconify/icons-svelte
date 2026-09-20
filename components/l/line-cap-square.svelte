<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jij_-4p-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jij_-4p-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:line-cap-square" {...props}></Icon>
