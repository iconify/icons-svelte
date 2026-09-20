<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wj7_yrpex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="wj7_yrpex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:attach-solid" {...props}></Icon>
