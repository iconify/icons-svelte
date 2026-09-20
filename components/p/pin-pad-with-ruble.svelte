<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v76j5s1uj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="v76j5s1uj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pin-pad-with-ruble" {...props}></Icon>
