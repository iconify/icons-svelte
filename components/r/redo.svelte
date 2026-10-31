<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/m/mnlfd9btk.css';
import '../../css/w/wakqt4bsh.css';
import '../../css/v/v_wmkzbwx.css';
import '../../css/v/vds-qfbri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="mnlfd9btk wm-shadow"/><path class="wakqt4bsh wm-shadow"/><path class="v_wmkzbwx"/><path class="vds-qfbri"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:redo" {...props}></Icon>
