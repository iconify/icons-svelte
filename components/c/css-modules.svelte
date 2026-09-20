<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1updhlbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x1updhlbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:css-modules" {...props}></Icon>
