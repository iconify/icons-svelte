<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-d3uqbve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t-d3uqbve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:dice-sharp" {...props}></Icon>
