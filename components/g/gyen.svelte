<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jjjf15bam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jjjf15bam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:gyen" {...props}></Icon>
