<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d4994ssvl.css';
import '../../css/m/m5h3s7x3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="d4994ssvl"/><path class="m5h3s7x3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:download" {...props}></Icon>
