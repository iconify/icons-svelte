<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/z9htctbmx.css';
import '../../css/i/iuz2rob6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="z9htctbmx"/><path clip-rule="evenodd" class="iuz2rob6a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:flashlight-flat" {...props}></Icon>
