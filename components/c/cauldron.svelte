<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohs3nursk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ohs3nursk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:cauldron" {...props}></Icon>
