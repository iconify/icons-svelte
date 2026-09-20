<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vbq3xlb_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vbq3xlb_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:jfrog" {...props}></Icon>
