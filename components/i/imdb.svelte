<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gmf2d63wb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gmf2d63wb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:imdb" {...props}></Icon>
