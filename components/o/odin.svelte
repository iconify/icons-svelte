<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v24ulvjer.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":260,"height":260};
const content = `<path class="v24ulvjer"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:odin" {...props}></Icon>
