<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jgi5qbc8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jgi5qbc8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:bike" {...props}></Icon>
