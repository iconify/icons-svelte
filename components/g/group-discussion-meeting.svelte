<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwhhydjyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vwhhydjyh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:group-discussion-meeting" {...props}></Icon>
