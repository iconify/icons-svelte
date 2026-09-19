<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sgwaxk78b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="sgwaxk78b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:pin" {...props}></Icon>
