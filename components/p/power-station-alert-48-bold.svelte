<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfi146w-l.css';
import '../../css/e/eeps4wpgj.css';
import '../../css/y/ygtv74bcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pfi146w-l"/><path class="eeps4wpgj"/><path class="ygtv74bcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:power-station-alert-48-bold" {...props}></Icon>
