<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nuxlfd-qn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nuxlfd-qn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:map-pin-plus" {...props}></Icon>
