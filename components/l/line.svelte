<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhl0rzsph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jhl0rzsph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:line" {...props}></Icon>
