<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pv_hji6de.css';
import '../../css/u/uhyw2tdeb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pv_hji6de"/><path clip-rule="evenodd" class="uhyw2tdeb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:camera-square-bold-duotone" {...props}></Icon>
