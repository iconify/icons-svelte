<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pkb4mob0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pkb4mob0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:cannabis-solid" {...props}></Icon>
