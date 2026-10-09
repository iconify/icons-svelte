<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-vml9bmf.css';
import '../../css/j/j8fkx09kt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="z-vml9bmf"/><path class="j8fkx09kt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:interconnector-48" {...props}></Icon>
