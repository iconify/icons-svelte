<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/ez1w_-48b.css';
import '../../css/n/n2o6cebib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ez1w_-48b"/><path class="n2o6cebib"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:ai-smartphone-duotone" {...props}></Icon>
