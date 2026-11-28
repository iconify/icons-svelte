<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/w/wlrfrla8c.css';
import '../../css/z/z_rsq7q-q.css';
import '../../css/k/k8r60b5kl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="wlrfrla8c"/><path class="z_rsq7q-q"/><path class="k8r60b5kl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:remote" {...props}></Icon>
