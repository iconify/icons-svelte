<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dcsdb2bla.css';
import '../../css/c/cpwldbcex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="dcsdb2bla"/><path class="cpwldbcex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:caravan" {...props}></Icon>
