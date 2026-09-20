<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u_g4grbdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="u_g4grbdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:commercial-15" {...props}></Icon>
