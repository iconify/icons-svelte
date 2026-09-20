<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pse_y4bkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="pse_y4bkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:loop" {...props}></Icon>
