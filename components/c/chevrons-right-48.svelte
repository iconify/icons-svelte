<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0obyhbch.css';
import '../../css/z/zlt4eiz7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="e0obyhbch"/><path class="zlt4eiz7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chevrons-right-48" {...props}></Icon>
