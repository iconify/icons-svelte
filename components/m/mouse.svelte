<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gvdokvbmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gvdokvbmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:mouse" {...props}></Icon>
