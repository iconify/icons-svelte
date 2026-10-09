<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8dcesb7n.css';
import '../../css/s/sb555ccjn.css';
import '../../css/v/vtvsuobia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="j8dcesb7n"/><path class="sb555ccjn"/><path class="vtvsuobia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pipeline-48" {...props}></Icon>
