<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwz5z9bar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uwz5z9bar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:message" {...props}></Icon>
