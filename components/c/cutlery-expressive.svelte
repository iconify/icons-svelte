<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o7el2-bsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":25};
const content = `<path class="o7el2-bsl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:cutlery-expressive" {...props}></Icon>
