<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mqijn-bno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mqijn-bno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:building-x" {...props}></Icon>
