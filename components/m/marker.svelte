<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wvmu1sb1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="wvmu1sb1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:marker" {...props}></Icon>
