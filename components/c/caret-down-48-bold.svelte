<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tk0rhabac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tk0rhabac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:caret-down-48-bold" {...props}></Icon>
