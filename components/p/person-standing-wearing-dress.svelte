<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0le36bep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="r0le36bep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-standing-wearing-dress" {...props}></Icon>
