<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uteu266cv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uteu266cv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:check-circle" {...props}></Icon>
