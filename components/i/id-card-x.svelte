<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u_ld50e8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u_ld50e8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:id-card-x" {...props}></Icon>
