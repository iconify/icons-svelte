<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mp6ykob9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="mp6ykob9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pixel-arrows-left-right" {...props}></Icon>
