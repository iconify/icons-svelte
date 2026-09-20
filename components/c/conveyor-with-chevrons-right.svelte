<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hutmwzbyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hutmwzbyd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:conveyor-with-chevrons-right" {...props}></Icon>
