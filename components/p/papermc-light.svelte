<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qg99wcb4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qg99wcb4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:papermc-light" {...props}></Icon>
