<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zq-yft7qu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2225,"height":399};
const content = `<path clip-rule="evenodd" class="zq-yft7qu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:electronic-arts" {...props}></Icon>
