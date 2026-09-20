<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vba71sb7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vba71sb7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:proteus" {...props}></Icon>
