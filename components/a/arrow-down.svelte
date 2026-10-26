<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qsg68bc0n.css';
import '../../css/l/l24gqyb4l.css';
import '../../css/o/o5l66lh6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="qsg68bc0n"><path class="l24gqyb4l"/><path class="o5l66lh6m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="doodle-icons:arrow-down" {...props}></Icon>
