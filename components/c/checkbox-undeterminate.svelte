<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mptj2mbio.css';
import '../../css/w/w2nbqq6me.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mptj2mbio"/><path class="w2nbqq6me"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:checkbox-undeterminate" {...props}></Icon>
