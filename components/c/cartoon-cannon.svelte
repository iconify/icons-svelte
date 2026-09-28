<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xrmyc0byc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xrmyc0byc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:cartoon-cannon" {...props}></Icon>
