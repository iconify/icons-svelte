<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mpndxdbgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mpndxdbgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="doodle-icons:quote" {...props}></Icon>
