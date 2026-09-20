<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/ert4v1b8j.css';
import '../../css/g/g2h3upp2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ert4v1b8j"/><path class="g2h3upp2o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:pull-request-duotone" {...props}></Icon>
