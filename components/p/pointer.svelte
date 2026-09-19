<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m6iivnbuo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":638,"height":694};
const content = `<path class="m6iivnbuo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:pointer" {...props}></Icon>
