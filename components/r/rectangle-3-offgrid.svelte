<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vt1o8pbzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="vt1o8pbzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:rectangle-3-offgrid" {...props}></Icon>
