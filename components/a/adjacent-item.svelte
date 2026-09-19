<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/kc784jy4i.css';
import '../../css/d/d-7w0ebsy.css';
import '../../css/c/cri_8d0jy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="kc784jy4i"/><path class="d-7w0ebsy"/><path class="cri_8d0jy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:adjacent-item" {...props}></Icon>
