<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pz9-9zbsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="pz9-9zbsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:id-card" {...props}></Icon>
