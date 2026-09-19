<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eg26jqbpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="eg26jqbpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:plus-square-dotted" {...props}></Icon>
