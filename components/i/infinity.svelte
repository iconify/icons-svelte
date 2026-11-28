<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vaz-w9bjs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vaz-w9bjs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:infinity" {...props}></Icon>
