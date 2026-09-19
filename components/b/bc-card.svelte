<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/let3ambub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2368,"height":1664};
const content = `<path class="let3ambub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:bc-card" {...props}></Icon>
