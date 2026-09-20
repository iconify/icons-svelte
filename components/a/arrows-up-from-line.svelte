<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r554d955a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r554d955a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:arrows-up-from-line" {...props}></Icon>
