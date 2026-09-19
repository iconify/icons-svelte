<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jk3yze2hm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":897,"height":1025};
const content = `<path class="jk3yze2hm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:cctv" {...props}></Icon>
