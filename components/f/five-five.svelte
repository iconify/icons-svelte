<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wvf38_bdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wvf38_bdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:five-five" {...props}></Icon>
