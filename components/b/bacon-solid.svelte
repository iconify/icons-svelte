<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h112d1ovp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="h112d1ovp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:bacon-solid" {...props}></Icon>
