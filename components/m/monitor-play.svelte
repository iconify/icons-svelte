<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fsa2w0bko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fsa2w0bko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:monitor-play" {...props}></Icon>
