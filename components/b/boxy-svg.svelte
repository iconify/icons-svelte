<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vymw6t_6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vymw6t_6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:boxy-svg" {...props}></Icon>
