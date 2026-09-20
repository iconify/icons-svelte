<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_c7mud5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="n_c7mud5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:parachute" {...props}></Icon>
