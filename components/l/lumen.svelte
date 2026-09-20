<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eo5d2pbos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eo5d2pbos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:lumen" {...props}></Icon>
