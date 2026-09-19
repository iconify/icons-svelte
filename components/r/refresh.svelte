<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gjntb4z9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":750,"height":810};
const content = `<path class="gjntb4z9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:refresh" {...props}></Icon>
