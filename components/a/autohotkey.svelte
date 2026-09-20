<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dimodfu-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dimodfu-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:autohotkey" {...props}></Icon>
