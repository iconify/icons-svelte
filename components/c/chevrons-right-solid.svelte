<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6ve2ebwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h6ve2ebwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:chevrons-right-solid" {...props}></Icon>
