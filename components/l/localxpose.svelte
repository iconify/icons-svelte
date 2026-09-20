<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vf0y15byz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vf0y15byz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:localxpose" {...props}></Icon>
