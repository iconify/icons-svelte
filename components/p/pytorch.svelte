<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1glu3bqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p1glu3bqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:pytorch" {...props}></Icon>
