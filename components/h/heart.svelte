<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fhyruk5mc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fhyruk5mc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:heart" {...props}></Icon>
