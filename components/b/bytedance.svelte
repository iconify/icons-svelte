<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ul6d8o8hz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ul6d8o8hz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:bytedance" {...props}></Icon>
