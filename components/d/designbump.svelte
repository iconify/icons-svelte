<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0thd4b-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":360,"height":488};
const content = `<path class="r0thd4b-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:designbump" {...props}></Icon>
