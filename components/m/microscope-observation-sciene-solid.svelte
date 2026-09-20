<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/occ1h7r-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="occ1h7r-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:microscope-observation-sciene-solid" {...props}></Icon>
