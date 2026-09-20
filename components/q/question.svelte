<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/a/a6z4ynb6v.css';
import '../../css/f/fqf74lb2o.css';
import '../../css/v/v39n78vsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><circle class="a6z4ynb6v"/><circle class="fqf74lb2o"/><path class="v39n78vsr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:question" {...props}></Icon>
