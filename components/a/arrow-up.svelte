<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h0krs8b4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h0krs8b4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:arrow-up" {...props}></Icon>
