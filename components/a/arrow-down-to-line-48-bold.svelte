<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j50zvhxpr.css';
import '../../css/e/ey0nx0bof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="j50zvhxpr"/><path class="ey0nx0bof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:arrow-down-to-line-48-bold" {...props}></Icon>
