<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/he9jgm06g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="he9jgm06g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:circle-small" {...props}></Icon>
