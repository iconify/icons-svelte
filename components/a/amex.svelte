<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmf4qpbtt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mmf4qpbtt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:amex" {...props}></Icon>
