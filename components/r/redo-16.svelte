<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uj23f-m4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="uj23f-m4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:redo-16" {...props}></Icon>
