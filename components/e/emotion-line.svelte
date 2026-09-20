<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jrjemnb0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jrjemnb0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:emotion-line" {...props}></Icon>
