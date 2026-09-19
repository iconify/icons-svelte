<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j82-wlwsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="j82-wlwsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:precisecursor" {...props}></Icon>
