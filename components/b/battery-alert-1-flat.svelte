<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/chm2o30cw.css';
import '../../css/r/rbkq9c8mn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g class="ft5dv1b6b"><path class="chm2o30cw"/><path clip-rule="evenodd" class="rbkq9c8mn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:battery-alert-1-flat" {...props}></Icon>
