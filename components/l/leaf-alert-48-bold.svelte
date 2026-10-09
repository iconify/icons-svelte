<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qgde9kd7j.css';
import '../../css/u/ui4laccyj.css';
import '../../css/x/x-w4dbc6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qgde9kd7j"/><path class="ui4laccyj"/><path class="x-w4dbc6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:leaf-alert-48-bold" {...props}></Icon>
