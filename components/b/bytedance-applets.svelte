<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jp4nthbbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jp4nthbbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:bytedance-applets" {...props}></Icon>
