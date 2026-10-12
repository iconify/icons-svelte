<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/h8ylcx8ej.css';
import '../../css/g/gc9u-abbc.css';
import '../../css/b/bhy-1cb-u.css';
import '../../css/x/x1twb64si.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="h8ylcx8ej"/><path class="gc9u-abbc"/><path class="bhy-1cb-u"/><path class="x1twb64si"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:armchair-duotone" {...props}></Icon>
