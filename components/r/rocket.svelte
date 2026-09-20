<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqibyvg5x.css';
import '../../css/w/wwyne7smp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="iqibyvg5x"/><path class="wwyne7smp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:rocket" {...props}></Icon>
