<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tfu98d8ng.css';
import '../../css/p/pdm5qacug.css';
import '../../css/a/a-9h4gbxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tfu98d8ng"/><path class="pdm5qacug"/><path class="a-9h4gbxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:palm-tree-48-bold" {...props}></Icon>
