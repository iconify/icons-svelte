<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5cg8fb9r.css';
import '../../css/g/g21s66bzs.css';
import '../../css/x/xlcp1d9yz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="y5cg8fb9r"><path class="g21s66bzs"/><path class="xlcp1d9yz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:hockey" {...props}></Icon>
