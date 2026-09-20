<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3ya7hera.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x3ya7hera"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:arrow-break" {...props}></Icon>
