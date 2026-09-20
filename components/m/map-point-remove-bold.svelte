<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fheh_03mf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fheh_03mf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:map-point-remove-bold" {...props}></Icon>
