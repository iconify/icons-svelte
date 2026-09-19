<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-x0dsblc.css';
import '../../css/m/m3qytymuy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="o-x0dsblc"/><path class="m3qytymuy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:forward-10" {...props}></Icon>
