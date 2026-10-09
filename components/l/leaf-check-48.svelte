<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/viu8vyokx.css';
import '../../css/j/jyz_jvb2h.css';
import '../../css/i/ihicaccwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="viu8vyokx"/><path class="jyz_jvb2h"/><path class="ihicaccwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:leaf-check-48" {...props}></Icon>
