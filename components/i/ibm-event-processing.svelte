<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_jtf253g.css';
import '../../css/d/d9g4t29kt.css';
import '../../css/x/x3zud0byo.css';
import '../../css/x/x9lkoi69j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="a_jtf253g"/><path class="d9g4t29kt"/><circle class="x3zud0byo"/><path class="x9lkoi69j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-event-processing" {...props}></Icon>
