<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ie0mq3i_d.css';
import '../../css/k/kgzgwquda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ie0mq3i_d"/><path class="kgzgwquda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:envelope" {...props}></Icon>
