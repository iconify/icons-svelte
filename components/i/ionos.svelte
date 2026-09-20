<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jusmfow2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jusmfow2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:ionos" {...props}></Icon>
