<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/fjiz8hbrl.css';
import '../../css/r/rxa1r_t5i.css';
import '../../css/h/h5_ubqi0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="fjiz8hbrl"/><circle class="rxa1r_t5i"/><path class="h5_ubqi0k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:key-alt-duotone" {...props}></Icon>
