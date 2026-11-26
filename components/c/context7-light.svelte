<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/xcripvb-d.css';
import '../../css/q/qi9jmsbwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":28};
const content = `<g class="ft5dv1b6b"><rect class="xcripvb-d"/><path class="qi9jmsbwa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:context7-light" {...props}></Icon>
