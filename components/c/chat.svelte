<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjl5eprxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cjl5eprxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:chat" {...props}></Icon>
