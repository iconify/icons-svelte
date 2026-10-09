<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l8l_jsz-q.css';
import '../../css/r/rodd6kbsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="l8l_jsz-q"/><path class="rodd6kbsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:flag-48-bold" {...props}></Icon>
