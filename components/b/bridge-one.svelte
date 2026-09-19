<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uifgws5er.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="uifgws5er"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:bridge-one" {...props}></Icon>
