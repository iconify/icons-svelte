<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jyr7ylbfe.css';
import '../../css/h/h7wrbubgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jyr7ylbfe"/><path class="h7wrbubgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:instrument-saxophone" {...props}></Icon>
