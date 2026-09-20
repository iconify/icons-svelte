<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flen3tbdj.css';
import '../../css/m/mu8evp9-u.css';
import '../../css/z/za2b-fbhg.css';
import '../../css/m/mof3eqe_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><rect transform="rotate(90 18 15)" class="mu8evp9-u"/><rect transform="rotate(-90 6 8)" class="za2b-fbhg"/><path class="mof3eqe_o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:nesting" {...props}></Icon>
