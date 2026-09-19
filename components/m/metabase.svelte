<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cr3yo8b8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="cr3yo8b8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:metabase" {...props}></Icon>
