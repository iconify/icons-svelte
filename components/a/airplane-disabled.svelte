<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqax-6b-d.css';
import '../../css/y/yq7arhh0q.css';
import '../../css/o/o101-2bhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="jqax-6b-d"><path class="yq7arhh0q"/><path class="o101-2bhf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:airplane-disabled" {...props}></Icon>
