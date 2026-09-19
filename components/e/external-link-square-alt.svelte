<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vtc58_b-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="vtc58_b-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:external-link-square-alt" {...props}></Icon>
