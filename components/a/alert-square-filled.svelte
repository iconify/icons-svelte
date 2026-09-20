<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdwtbc9eq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fdwtbc9eq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:alert-square-filled" {...props}></Icon>
