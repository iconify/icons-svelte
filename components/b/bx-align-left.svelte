<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u47opxhjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u47opxhjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-align-left" {...props}></Icon>
