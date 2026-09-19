<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/et57vxgoa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="et57vxgoa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:plus-a" {...props}></Icon>
