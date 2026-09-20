<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nht6o6bbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nht6o6bbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:fork" {...props}></Icon>
