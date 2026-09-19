<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxpt1mbov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="rxpt1mbov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:circle-line-stroke-12" {...props}></Icon>
