<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qq-v7yb2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qq-v7yb2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:lymph-nodes" {...props}></Icon>
