<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/shppmgbpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":704,"height":1024};
const content = `<path class="shppmgbpi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:handup" {...props}></Icon>
