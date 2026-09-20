<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9j1edudd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r9j1edudd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:add-task" {...props}></Icon>
