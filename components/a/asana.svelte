<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/if5b9ygfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":251,"height":232};
const content = `<path class="if5b9ygfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:asana" {...props}></Icon>
