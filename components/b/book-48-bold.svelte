<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6wbwjb8t.css';
import '../../css/x/xxkd03eis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="f6wbwjb8t"/><path class="xxkd03eis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:book-48-bold" {...props}></Icon>
