<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vs9dl9bml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="vs9dl9bml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:account-login" {...props}></Icon>
