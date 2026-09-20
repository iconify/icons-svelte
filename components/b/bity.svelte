<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o31m176dr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="o31m176dr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:bity" {...props}></Icon>
