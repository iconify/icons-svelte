<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hu22mfb8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="hu22mfb8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:bot-generic-26" {...props}></Icon>
