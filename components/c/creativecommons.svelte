<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2pfyrqig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="s2pfyrqig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:creativecommons" {...props}></Icon>
