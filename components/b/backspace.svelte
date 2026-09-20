<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rp-7lzc2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rp-7lzc2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:backspace" {...props}></Icon>
