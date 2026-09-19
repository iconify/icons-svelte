<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j3_2z0moj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":23,"height":24};
const content = `<path class="j3_2z0moj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:angle-dobule-up" {...props}></Icon>
