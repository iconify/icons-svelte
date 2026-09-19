<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ry8pu_a8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ry8pu_a8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:algolia" {...props}></Icon>
