<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdwk85bee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="mdwk85bee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:purse-filled" {...props}></Icon>
