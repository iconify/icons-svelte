<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pkk3kgb0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pkk3kgb0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:mountain" {...props}></Icon>
