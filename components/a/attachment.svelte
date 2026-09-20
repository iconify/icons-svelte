<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q53a_eb2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="q53a_eb2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="marketeq:attachment" {...props}></Icon>
