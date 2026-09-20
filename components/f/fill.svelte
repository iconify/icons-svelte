<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/soti_jvkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="soti_jvkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:fill" {...props}></Icon>
