<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/po7yq0b0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="po7yq0b0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:battery-upright-three-quarter" {...props}></Icon>
