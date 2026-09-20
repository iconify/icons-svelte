<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dwmun5b1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="dwmun5b1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:brush" {...props}></Icon>
