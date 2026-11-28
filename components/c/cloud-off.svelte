<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gu05dtbca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gu05dtbca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:cloud-off" {...props}></Icon>
