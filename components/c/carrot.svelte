<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f82dgl3aa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f82dgl3aa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:carrot" {...props}></Icon>
