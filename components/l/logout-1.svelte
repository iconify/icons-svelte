<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wbg8gpbbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="wbg8gpbbb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:logout-1" {...props}></Icon>
