<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ha0nppz8t.css';
import '../../css/h/hhk88wzsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ha0nppz8t"/><path class="hhk88wzsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:file-text" {...props}></Icon>
