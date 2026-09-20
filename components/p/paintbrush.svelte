<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_8egljzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="v_8egljzq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:paintbrush" {...props}></Icon>
