<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6smme34o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="h6smme34o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:microphone" {...props}></Icon>
