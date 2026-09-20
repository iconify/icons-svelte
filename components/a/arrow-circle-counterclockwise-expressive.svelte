<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e187webbi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e187webbi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:arrow-circle-counterclockwise-expressive" {...props}></Icon>
