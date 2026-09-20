<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/r/rbliukcje.css';
import '../../css/s/suo3rkklt.css';
import '../../css/v/v05-n5bad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="rbliukcje"/><path class="suo3rkklt"/><path class="v05-n5bad"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:keyboard-eject-button" {...props}></Icon>
