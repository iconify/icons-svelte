<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/veb_vob-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":962};
const content = `<path class="veb_vob-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:gears" {...props}></Icon>
