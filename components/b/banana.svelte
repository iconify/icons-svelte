<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n45puibir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n45puibir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:banana" {...props}></Icon>
