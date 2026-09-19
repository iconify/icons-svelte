<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8eeycb8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x8eeycb8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:invision" {...props}></Icon>
