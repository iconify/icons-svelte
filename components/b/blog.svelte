<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwskhw6wu.css';
import '../../css/j/jmbniybow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vwskhw6wu"/><path class="jmbniybow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:blog" {...props}></Icon>
