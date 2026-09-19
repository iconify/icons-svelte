<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_myqbbgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z_myqbbgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:amazon" {...props}></Icon>
