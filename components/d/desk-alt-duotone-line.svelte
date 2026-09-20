<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/aph6q2bxw.css';
import '../../css/z/zs5t2abgl.css';
import '../../css/c/cvpnadiui.css';
import '../../css/c/cogexj8lf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="aph6q2bxw"/><path class="zs5t2abgl"/><path class="cvpnadiui"/><path class="cogexj8lf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:desk-alt-duotone-line" {...props}></Icon>
