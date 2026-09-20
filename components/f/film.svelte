<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jge4mgh9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jge4mgh9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:film" {...props}></Icon>
