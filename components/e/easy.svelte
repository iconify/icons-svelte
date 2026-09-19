<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v8d_9eptl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="v8d_9eptl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:easy" {...props}></Icon>
