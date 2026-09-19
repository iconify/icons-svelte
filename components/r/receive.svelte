<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9cngdc1l.css';
import '../../css/e/ew7188tnn.css';
import '../../css/b/blb99bcah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2000,"height":2000};
const content = `<g class="o9cngdc1l"><path class="ew7188tnn"/><path class="blb99bcah"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:receive" {...props}></Icon>
