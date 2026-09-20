<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cb_hm7btx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="cb_hm7btx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:north-carolina" {...props}></Icon>
