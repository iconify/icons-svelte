<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3vs7td1h.css';
import '../../css/o/o2a1_1bbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="t3vs7td1h"/><path class="o2a1_1bbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:bomb" {...props}></Icon>
