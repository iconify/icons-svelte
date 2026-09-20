<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pvzfzdppk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pvzfzdppk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:paperclip" {...props}></Icon>
