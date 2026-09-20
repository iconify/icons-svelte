<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ra5ogubua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ra5ogubua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:bold-cyrl-te" {...props}></Icon>
