<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/epi81h6gk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="epi81h6gk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:coffee" {...props}></Icon>
