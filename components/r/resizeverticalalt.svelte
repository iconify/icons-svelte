<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nr81or0jr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="nr81or0jr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:resizeverticalalt" {...props}></Icon>
