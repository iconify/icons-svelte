<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xcf1f9bjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="xcf1f9bjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:erlang" {...props}></Icon>
