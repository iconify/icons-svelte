<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0t-jn1ns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e0t-jn1ns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:egg" {...props}></Icon>
