<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqax-6b-d.css';
import '../../css/m/m7x1a70ua.css';
import '../../css/x/xyu3ddcdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="jqax-6b-d"><path class="m7x1a70ua"/><path class="xyu3ddcdi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:hospital-sign-square" {...props}></Icon>
