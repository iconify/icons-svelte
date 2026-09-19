<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wed13veom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wed13veom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:arrow-right-circled" {...props}></Icon>
