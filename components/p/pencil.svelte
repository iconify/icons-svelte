<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7d_q8bib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j7d_q8bib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:pencil" {...props}></Icon>
