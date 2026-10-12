<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9ng43b9q.css';
import '../../css/z/zgpx6ybju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="n9ng43b9q"/><path class="zgpx6ybju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:oil-can-48-bold" {...props}></Icon>
