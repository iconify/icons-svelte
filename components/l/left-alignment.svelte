<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9pw6ooui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="m9pw6ooui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:left-alignment" {...props}></Icon>
