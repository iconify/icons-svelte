<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j9z1fbc2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j9z1fbc2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-ruler" {...props}></Icon>
