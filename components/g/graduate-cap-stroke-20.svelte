<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mwf0dbb6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mwf0dbb6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:graduate-cap-stroke-20" {...props}></Icon>
