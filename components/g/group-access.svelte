<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mj81mac8p.css';
import '../../css/b/b0-g4tear.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mj81mac8p"/><path class="b0-g4tear"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:group-access" {...props}></Icon>
