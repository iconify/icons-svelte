<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/m/mxaazra7v.css';
import '../../css/k/krogttbhn.css';
import '../../css/v/v-cwrbbvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="mxaazra7v"/><path class="krogttbhn"/><path class="v-cwrbbvd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:find" {...props}></Icon>
