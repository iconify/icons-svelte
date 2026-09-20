<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h7kouvc9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="h7kouvc9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:long-arrow-alt-down" {...props}></Icon>
