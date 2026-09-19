<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3c-6wbuu.css';
import '../../css/a/ali10ogyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="d3c-6wbuu"/><path class="ali10ogyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:circle-right" {...props}></Icon>
