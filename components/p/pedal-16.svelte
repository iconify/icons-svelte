<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1fgboumi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="j1fgboumi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:pedal-16" {...props}></Icon>
