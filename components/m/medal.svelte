<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i99h-_v1d.css';
import '../../css/x/xspkd8upa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="i99h-_v1d"/><path class="xspkd8upa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:medal" {...props}></Icon>
