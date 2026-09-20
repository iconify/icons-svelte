<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ra_8gx4bc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ra_8gx4bc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:baseten" {...props}></Icon>
