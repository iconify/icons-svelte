<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/o/opo1zcc8y.css';
import '../../css/o/o8cb350vf.css';
import '../../css/e/em4i2mbry.css';
import '../../css/a/am077nbxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="opo1zcc8y"/><path class="o8cb350vf"/><path class="em4i2mbry"/><path class="am077nbxd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:app-window-link" {...props}></Icon>
