<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipt9fhbmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ipt9fhbmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:arrow-down-solid" {...props}></Icon>
