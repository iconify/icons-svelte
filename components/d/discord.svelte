<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fk9zmhbik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fk9zmhbik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:discord" {...props}></Icon>
