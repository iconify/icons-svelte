<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mej7m02qn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mej7m02qn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:flask-minus-outline" {...props}></Icon>
