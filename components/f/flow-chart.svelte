<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tkhi9lbht.css';
import '../../css/q/qvchyyb3r.css';
import '../../css/s/svglptr5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tkhi9lbht"/><path class="qvchyyb3r"/><path class="svglptr5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:flow-chart" {...props}></Icon>
