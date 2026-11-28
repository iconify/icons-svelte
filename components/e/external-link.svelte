<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4h2do-8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f4h2do-8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:external-link" {...props}></Icon>
