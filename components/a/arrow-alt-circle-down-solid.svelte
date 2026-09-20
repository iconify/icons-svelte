<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m6ug91b-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="m6ug91b-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:arrow-alt-circle-down-solid" {...props}></Icon>
