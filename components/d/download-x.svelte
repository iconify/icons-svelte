<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o886_iy8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o886_iy8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:download-x" {...props}></Icon>
