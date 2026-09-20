<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/li7mzybab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="li7mzybab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:lock-unlocked" {...props}></Icon>
