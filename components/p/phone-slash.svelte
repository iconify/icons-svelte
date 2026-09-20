<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_afapeoj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="f_afapeoj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:phone-slash" {...props}></Icon>
