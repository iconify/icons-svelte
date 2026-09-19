<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9wiuwgzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="w9wiuwgzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:facebook-messenger" {...props}></Icon>
