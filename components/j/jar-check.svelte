<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fw3pl2qrd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fw3pl2qrd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:jar-check" {...props}></Icon>
