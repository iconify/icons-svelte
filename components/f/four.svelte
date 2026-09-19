<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qhc0zl4zk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qhc0zl4zk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:four" {...props}></Icon>
