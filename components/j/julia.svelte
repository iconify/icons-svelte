<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rcahgwb3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rcahgwb3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:julia" {...props}></Icon>
