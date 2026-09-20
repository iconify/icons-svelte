<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxtpv0web.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oxtpv0web"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:openmined" {...props}></Icon>
