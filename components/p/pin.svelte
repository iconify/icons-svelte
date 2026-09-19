<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_m274e1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="e_m274e1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:pin" {...props}></Icon>
