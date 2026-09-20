<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wci50ybup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="wci50ybup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:lua" {...props}></Icon>
