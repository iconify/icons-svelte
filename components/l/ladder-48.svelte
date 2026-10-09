<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l8tp9mb-t.css';
import '../../css/w/wrzecibmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="l8tp9mb-t"/><path class="wrzecibmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ladder-48" {...props}></Icon>
