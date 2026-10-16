<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rz1qd9m1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rz1qd9m1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:memos-light" {...props}></Icon>
