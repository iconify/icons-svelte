<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ngyvv5bhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="ngyvv5bhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:battery-0" {...props}></Icon>
