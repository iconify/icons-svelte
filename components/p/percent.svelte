<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i28_uy10g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="i28_uy10g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:percent" {...props}></Icon>
