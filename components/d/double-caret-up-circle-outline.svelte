<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lpm3sabez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lpm3sabez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:double-caret-up-circle-outline" {...props}></Icon>
