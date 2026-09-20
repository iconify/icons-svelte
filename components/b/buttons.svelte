<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nx_19xfxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="nx_19xfxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:buttons" {...props}></Icon>
