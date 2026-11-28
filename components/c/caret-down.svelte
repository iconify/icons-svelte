<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cpu-x5tjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cpu-x5tjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:caret-down" {...props}></Icon>
