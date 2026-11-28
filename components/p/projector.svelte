<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fj5stg2zm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fj5stg2zm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:projector" {...props}></Icon>
