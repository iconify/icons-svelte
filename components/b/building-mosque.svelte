<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/guf9n9spv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="guf9n9spv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:building-mosque" {...props}></Icon>
