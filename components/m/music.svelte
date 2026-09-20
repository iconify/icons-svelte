<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x29ck_k2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="x29ck_k2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:music" {...props}></Icon>
