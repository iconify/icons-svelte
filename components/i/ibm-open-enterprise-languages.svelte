<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dxlye1b8h.css';
import '../../css/o/o8elwl8sg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dxlye1b8h"/><path class="o8elwl8sg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-open-enterprise-languages" {...props}></Icon>
