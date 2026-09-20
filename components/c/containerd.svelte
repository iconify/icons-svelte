<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oc5kx8b5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oc5kx8b5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:containerd" {...props}></Icon>
