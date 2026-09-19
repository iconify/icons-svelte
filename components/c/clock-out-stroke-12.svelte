<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a1qje2naz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="a1qje2naz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:clock-out-stroke-12" {...props}></Icon>
