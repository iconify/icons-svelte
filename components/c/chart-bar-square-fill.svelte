<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wj14-pijc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="wj14-pijc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:chart-bar-square-fill" {...props}></Icon>
