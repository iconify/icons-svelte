<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ia7l2rsyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ia7l2rsyj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:medium" {...props}></Icon>
