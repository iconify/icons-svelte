<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mzzslfcdm.css';
import '../../css/l/lsa0pyl4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mzzslfcdm"/><path clip-rule="evenodd" class="lsa0pyl4w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:double-heart-flat" {...props}></Icon>
