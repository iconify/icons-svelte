<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qkf_nqv3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":65,"height":65,"left":33};
const content = `<path class="qkf_nqv3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:chunk-dark" {...props}></Icon>
