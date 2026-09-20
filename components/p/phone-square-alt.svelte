<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/irpm2abtr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="irpm2abtr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:phone-square-alt" {...props}></Icon>
