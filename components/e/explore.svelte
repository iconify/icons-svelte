<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/utt_0ki8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="utt_0ki8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:explore" {...props}></Icon>
