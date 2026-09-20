<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/idpi_1brs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="idpi_1brs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:pexels" {...props}></Icon>
