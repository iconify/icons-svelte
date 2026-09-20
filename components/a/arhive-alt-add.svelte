<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flen3tbdj.css';
import '../../css/n/nf6zy_b6r.css';
import '../../css/m/mr4ysib0c.css';
import '../../css/e/em93k3h0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><path class="nf6zy_b6r"/><path class="mr4ysib0c"/><path class="em93k3h0f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:arhive-alt-add" {...props}></Icon>
