<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yvim8zbts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="yvim8zbts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:language" {...props}></Icon>
