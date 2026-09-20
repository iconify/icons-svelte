<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/x83nd5bnd.css';
import '../../css/t/tet0_objy.css';
import '../../css/l/ler2aibxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="ft5dv1b6b"><rect class="x83nd5bnd"/><path clip-rule="evenodd" class="tet0_objy"/><path class="ler2aibxt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="skill-icons:appwrite" {...props}></Icon>
