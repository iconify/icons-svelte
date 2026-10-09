<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qgde9kd7j.css';
import '../../css/u/ui4laccyj.css';
import '../../css/y/yc_dsr88x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qgde9kd7j"/><path class="ui4laccyj"/><path class="yc_dsr88x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:leaf-check-48-bold" {...props}></Icon>
