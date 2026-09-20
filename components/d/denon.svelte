<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ztey5v61a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ztey5v61a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:denon" {...props}></Icon>
