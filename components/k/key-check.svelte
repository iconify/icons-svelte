<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jnk4ipbkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jnk4ipbkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:key-check" {...props}></Icon>
