<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/sp1rtvb2c.css';
import '../../css/i/igde2ez5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="sp1rtvb2c"/><path clip-rule="evenodd" class="igde2ez5w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:dial-pad-finger-2-flat" {...props}></Icon>
