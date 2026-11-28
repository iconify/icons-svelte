<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxn7ngb1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gxn7ngb1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:coins-plus" {...props}></Icon>
