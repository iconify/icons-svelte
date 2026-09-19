<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s78ylohav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="s78ylohav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:fish2-sad" {...props}></Icon>
