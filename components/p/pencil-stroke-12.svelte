<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oke2ykbej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="oke2ykbej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:pencil-stroke-12" {...props}></Icon>
