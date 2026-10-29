<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/myk9ll1ec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="myk9ll1ec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:parking-solid" {...props}></Icon>
