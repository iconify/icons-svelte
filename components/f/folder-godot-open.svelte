<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qa0d9wb7d.css';
import '../../css/r/rz1q6nuvq.css';
import '../../css/x/xrnpo0biw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qa0d9wb7d"/><path class="rz1q6nuvq"/><path class="xrnpo0biw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-godot-open" {...props}></Icon>
