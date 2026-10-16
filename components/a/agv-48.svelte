<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3l0q_b-c.css';
import '../../css/q/qdnhae7pn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="s3l0q_b-c"/><path class="qdnhae7pn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:agv-48" {...props}></Icon>
