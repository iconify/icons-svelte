<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f252ndbns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f252ndbns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:engine" {...props}></Icon>
