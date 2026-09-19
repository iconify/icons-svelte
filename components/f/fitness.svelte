<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ct2_n2buj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ct2_n2buj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:fitness" {...props}></Icon>
