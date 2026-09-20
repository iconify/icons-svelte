<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahnu4ffkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ahnu4ffkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:hangar" {...props}></Icon>
