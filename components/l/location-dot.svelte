<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z25walbuz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="z25walbuz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:location-dot" {...props}></Icon>
