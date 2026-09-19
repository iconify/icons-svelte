<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wt9pubbnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="wt9pubbnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:network" {...props}></Icon>
