<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/waw60ab1f.css';
import '../../css/c/cd-eh4cev.css';
import '../../css/b/b50gwx6hj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="waw60ab1f"/><path class="cd-eh4cev"/><path class="b50gwx6hj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:heat-exchanger-48" {...props}></Icon>
