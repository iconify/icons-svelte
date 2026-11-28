<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h65ixdb0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h65ixdb0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:log" {...props}></Icon>
