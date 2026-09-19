<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jvatv5_qi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jvatv5_qi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:bulb-group-bollard-wall-appear" {...props}></Icon>
