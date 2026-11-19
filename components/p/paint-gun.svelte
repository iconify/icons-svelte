<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/p/p20adwbpg.css';
import '../../css/o/oua8bue4c.css';
import '../../css/c/c-hdtesmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="p20adwbpg"/><path class="oua8bue4c"/><rect class="c-hdtesmm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:paint-gun" {...props}></Icon>
