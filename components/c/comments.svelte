<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rjws7nb3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":31,"height":24};
const content = `<path class="rjws7nb3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:comments" {...props}></Icon>
