<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wae55l3tx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wae55l3tx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:expressdotjs-dark" {...props}></Icon>
