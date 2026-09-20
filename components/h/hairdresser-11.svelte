<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/riuiy0bck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="riuiy0bck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:hairdresser-11" {...props}></Icon>
