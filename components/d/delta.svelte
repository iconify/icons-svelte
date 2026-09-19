<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/si6upyb3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="si6upyb3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:delta" {...props}></Icon>
