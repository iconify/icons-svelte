<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-lzoc2ky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="x-lzoc2ky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:expand-full" {...props}></Icon>
