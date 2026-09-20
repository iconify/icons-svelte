<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wzup_wbcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="wzup_wbcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:cow" {...props}></Icon>
