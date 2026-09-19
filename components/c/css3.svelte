<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jy65xx2-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1600};
const content = `<path class="jy65xx2-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:css3" {...props}></Icon>
