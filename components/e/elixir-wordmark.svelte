<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fozui9hfo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="fozui9hfo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:elixir-wordmark" {...props}></Icon>
