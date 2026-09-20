<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqqtj5ncr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="iqqtj5ncr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:photo" {...props}></Icon>
